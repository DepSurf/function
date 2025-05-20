# Function: <code>populate_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106c9e0)
Location: arch/x86/mm/pageattr.c:927
Inline: False
```
**Symbols:**

```
ffffffff8106c9e0-ffffffff8106cc88: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106c6b0)
Location: arch/x86/mm/pageattr.c:920
Inline: False
```
**Symbols:**

```
ffffffff8106c6b0-ffffffff8106c968: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810702f0)
Location: arch/x86/mm/pageattr.c:920
Inline: False
```
**Symbols:**

```
ffffffff810702f0-ffffffff810705a8: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106fa20)
Location: arch/x86/mm/pageattr.c:956
Inline: False
```
**Symbols:**

```
ffffffff8106fa20-ffffffff8106fcf1: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81074e90)
Location: arch/x86/mm/pageattr.c:956
Inline: False
```
**Symbols:**

```
ffffffff81074e90-ffffffff81075198: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810778b0)
Location: arch/x86/mm/pageattr.c:967
Inline: False
```
**Symbols:**

```
ffffffff810778b0-ffffffff81077c00: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107e060)
Location: arch/x86/mm/pageattr.c:1229
Inline: False
```
**Symbols:**

```
ffffffff8107e060-ffffffff8107e3b0: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081960)
Location: arch/x86/mm/pageattr.c:1239
Inline: False
```
**Symbols:**

```
ffffffff81081960-ffffffff81081ca3: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81082a20)
Location: arch/x86/mm/pageattr.c:1239
Inline: False
```
**Symbols:**

```
ffffffff81082a20-ffffffff81082d63: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c140)
Location: arch/x86/mm/pat/set_memory.c:1259
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
**Symbols:**

```
ffffffff8108c140-ffffffff8108c469: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c3e0)
Location: arch/x86/mm/pat/set_memory.c:1259
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
**Symbols:**

```
ffffffff8108c3e0-ffffffff8108c709: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ce20)
Location: arch/x86/mm/pat/set_memory.c:1267
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
**Symbols:**

```
ffffffff8108ce20-ffffffff8108d135: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c6a0)
Location: arch/x86/mm/pat/set_memory.c:1267
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
**Symbols:**

```
ffffffff8109c6a0-ffffffff8109c9b1: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810afe50)
Location: arch/x86/mm/pat/set_memory.c:1259
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
**Symbols:**

```
ffffffff810afe50-ffffffff810b01c7: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca4d0)
Location: arch/x86/mm/pat/set_memory.c:1336
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
**Symbols:**

```
ffffffff810ca4d0-ffffffff810ca84a: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdb10)
Location: arch/x86/mm/pat/set_memory.c:1337
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
**Symbols:**

```
ffffffff810cdb10-ffffffff810cde8a: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d61f0)
Location: arch/x86/mm/pat/set_memory.c:1341
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
**Symbols:**

```
ffffffff810d61f0-ffffffff810d656a: populate_pmd (STB_LOCAL)
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
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081a20)
Location: arch/x86/mm/pageattr.c:1239
Inline: False
```
**Symbols:**

```
ffffffff81081a20-ffffffff81081d63: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81070820)
Location: arch/x86/mm/pageattr.c:1239
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pgd
```
**Symbols:**

```
ffffffff81070820-ffffffff81070b42: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810819d0)
Location: arch/x86/mm/pageattr.c:1239
Inline: False
```
**Symbols:**

```
ffffffff810819d0-ffffffff81081d13: populate_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int populate_pmd(struct cpa_data *cpa, long unsigned int start, long unsigned int end, unsigned int num_pages, pud_t *pud, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083af0)
Location: arch/x86/mm/pageattr.c:1239
Inline: False
```
**Symbols:**

```
ffffffff81083af0-ffffffff81083e33: populate_pmd (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
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
